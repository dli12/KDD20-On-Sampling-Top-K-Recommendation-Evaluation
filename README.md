# On-sampling-Top-K-Recommendation-Evaluation
## - FIGURE
## 1. (Figure 1)

<img src="./figures/figure1/P.png" width="425"/> <img src="./figures/figure1/S.png" width="425"/> 

## 2. (Figure 2 - 6)

<img src="./figures/figure23456/fig2_p.png" width="425"/> 
<img src="./figures/figure23456/fig3.PNG" width="425"/> 
<img src="./figures/figure23456/fig4.PNG" width="425"/> 
<img src="./figures/figure23456/fig5.PNG" width="425"/> 
<img src="./figures/figure23456/fig6.png" width="425"/> 

## 3. (Figure 7)

<img src="./figures/figure7/EASE-ML1M-N.png" width="425"/> <img src="./figures/figure7/EASE-ML1M-S.png" width="425"/> 
<img src="./figures/figure7/KNN-YELP-N.png" width="425"/> <img src="./figures/figure7/KNN-YELP-S.png" width="425"/> 
<img src="./figures/figure7/NCF-YELP-N.png" width="425"/> <img src="./figures/figure7/NCF-YELP-S.png" width="425"/> 
<img src="./figures/figure7/VAE-ML1M-N.png" width="425"/> <img src="./figures/figure7/VAE-ML1M-S.png" width="425"/> 

## 4. (Figure 8)
<img src="./figures/figure8/ALS_X.png" width="425"/>
<img src="./figures/figure8/NCF_X.png" width="425"/> 
<img src="./figures/figure8/VAE_X.png" width="425"/> 

## - TABLE
## 1. Varing Sampling Top *k* (Table 3, Table 4)

- **Varing Sampling Top k on MultiVAE:ml-1m:n=100**

<table border=0 cellpadding=0 cellspacing=0 width=1653 style='border-collapse:
 collapse;table-layout:fixed;width:1235pt'>
 <col class=xl65 width=87 span=2 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 span=15 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 width=87 style='height:19.0pt;width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black'>n = 100,
  MultiVAE-ml-1m,binom</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 100, MultiVAE-ml-1m,hyper</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 100, MultiVAE-ml-1m,actual</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>1</td>
  <td class=xl69>0.1031</td>
  <td class=xl69>0.0007</td>
  <td class=xl70>0.0442</td>
  <td class=xl69>0.1116</td>
  <td class=xl71>0.0829</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.1012</td>
  <td class=xl69>0.0007</td>
  <td class=xl70>0.0442</td>
  <td class=xl69>0.1116</td>
  <td class=xl71>0.0829</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.2101</td>
  <td class=xl69>0.0137</td>
  <td class=xl70>0.1608</td>
  <td class=xl69>0.2540</td>
  <td class=xl71>0.2161</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>2</td>
  <td class=xl69>0.2041</td>
  <td class=xl69>0.1116</td>
  <td class=xl70>0.1700</td>
  <td class=xl69>0.2185</td>
  <td class=xl71>0.2012</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.1964</td>
  <td class=xl69>0.1116</td>
  <td class=xl70>0.1700</td>
  <td class=xl69>0.2185</td>
  <td class=xl71>0.2012</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.3349</td>
  <td class=xl69>0.2540</td>
  <td class=xl70>0.3199</td>
  <td class=xl69>0.3810</td>
  <td class=xl71>0.3555</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>5</td>
  <td class=xl69>0.4157</td>
  <td class=xl69>0.3745</td>
  <td class=xl70>0.4050</td>
  <td class=xl69>0.4334</td>
  <td class=xl71>0.4209</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.4119</td>
  <td class=xl69>0.3745</td>
  <td class=xl70>0.4050</td>
  <td class=xl69>0.4334</td>
  <td class=xl71>0.4209</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.5533</td>
  <td class=xl69>0.5359</td>
  <td class=xl70>0.5603</td>
  <td class=xl69>0.5889</td>
  <td class=xl71>0.5768</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>10</td>
  <td class=xl69>0.6200</td>
  <td class=xl69>0.6048</td>
  <td class=xl70>0.6204</td>
  <td class=xl69>0.6323</td>
  <td class=xl71>0.6258</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.6157</td>
  <td class=xl69>0.6048</td>
  <td class=xl70>0.6204</td>
  <td class=xl69>0.6323</td>
  <td class=xl71>0.6258</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.7164</td>
  <td class=xl69>0.7192</td>
  <td class=xl70>0.7295</td>
  <td class=xl69>0.7391</td>
  <td class=xl71>0.7334</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>20</td>
  <td class=xl69>0.7992</td>
  <td class=xl69>0.7952</td>
  <td class=xl70>0.8012</td>
  <td class=xl69>0.8050</td>
  <td class=xl71>0.8028</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.7975</td>
  <td class=xl69>0.7952</td>
  <td class=xl70>0.8012</td>
  <td class=xl69>0.8050</td>
  <td class=xl71>0.8028</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8531</td>
  <td class=xl69>0.8608</td>
  <td class=xl70>0.8661</td>
  <td class=xl69>0.8690</td>
  <td class=xl71>0.8674</td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td class=xl72>50</td>
  <td class=xl73>0.9651</td>
  <td class=xl73>0.9671</td>
  <td class=xl74>0.9682</td>
  <td class=xl73>0.9684</td>
  <td class=xl75>0.9682</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9661</td>
  <td class=xl73>0.9671</td>
  <td class=xl74>0.9682</td>
  <td class=xl73>0.9684</td>
  <td class=xl75>0.9682</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9757</td>
  <td class=xl73>0.9795</td>
  <td class=xl74>0.9800</td>
  <td class=xl73>0.9803</td>
  <td class=xl75>0.9798</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>


- **Varing Sampling Top k on MultiVAE:ml-1m:n=1000**

<table border=0 cellpadding=0 cellspacing=0 width=1653 style='border-collapse:
 collapse;table-layout:fixed;width:1235pt'>
 <col class=xl65 width=87 span=2 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 span=15 style='width:65pt'>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 width=87 style='height:19.0pt;width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black'>n = 1000,
  MultiVAE-ml-1m,binom</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 1000, MultiVAE-ml-1m,hyper</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 1000, MultiVAE-ml-1m,actual</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>1</td>
  <td class=xl69>0.1091</td>
  <td class=xl69>0.0957</td>
  <td class=xl70>0.0998</td>
  <td class=xl69>0.1116</td>
  <td class=xl71>0.1089</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.1096</td>
  <td class=xl69>0.0957</td>
  <td class=xl70>0.0998</td>
  <td class=xl69>0.1116</td>
  <td class=xl71>0.1089</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.2417</td>
  <td class=xl69>0.2377</td>
  <td class=xl70>0.2407</td>
  <td class=xl69>0.2540</td>
  <td class=xl71>0.2495</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>2</td>
  <td class=xl69>0.2126</td>
  <td class=xl69>0.2099</td>
  <td class=xl70>0.2124</td>
  <td class=xl69>0.2185</td>
  <td class=xl71>0.2174</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.2126</td>
  <td class=xl69>0.2099</td>
  <td class=xl70>0.2124</td>
  <td class=xl69>0.2185</td>
  <td class=xl71>0.2174</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.3682</td>
  <td class=xl69>0.3669</td>
  <td class=xl70>0.3704</td>
  <td class=xl69>0.3810</td>
  <td class=xl71>0.3770</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>5</td>
  <td class=xl69>0.4281</td>
  <td class=xl69>0.4286</td>
  <td class=xl70>0.4306</td>
  <td class=xl69>0.4334</td>
  <td class=xl71>0.4318</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.4290</td>
  <td class=xl69>0.4286</td>
  <td class=xl70>0.4306</td>
  <td class=xl69>0.4334</td>
  <td class=xl71>0.4318</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.5776</td>
  <td class=xl69>0.5848</td>
  <td class=xl70>0.5861</td>
  <td class=xl69>0.5889</td>
  <td class=xl71>0.5874</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>10</td>
  <td class=xl69>0.6293</td>
  <td class=xl69>0.6296</td>
  <td class=xl70>0.6303</td>
  <td class=xl69>0.6316</td>
  <td class=xl71>0.6316</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.6315</td>
  <td class=xl69>0.6296</td>
  <td class=xl70>0.6303</td>
  <td class=xl69>0.6316</td>
  <td class=xl71>0.6316</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.7286</td>
  <td class=xl69>0.7376</td>
  <td class=xl70>0.7381</td>
  <td class=xl69>0.7389</td>
  <td class=xl71>0.7389</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>20</td>
  <td class=xl69>0.8036</td>
  <td class=xl69>0.8040</td>
  <td class=xl70>0.8043</td>
  <td class=xl69>0.8050</td>
  <td class=xl71>0.8046</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8060</td>
  <td class=xl69>0.8040</td>
  <td class=xl70>0.8043</td>
  <td class=xl69>0.8050</td>
  <td class=xl71>0.8046</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8570</td>
  <td class=xl69>0.8679</td>
  <td class=xl70>0.8684</td>
  <td class=xl69>0.8690</td>
  <td class=xl71>0.8689</td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td class=xl72>50</td>
  <td class=xl73>0.9672</td>
  <td class=xl73>0.9682</td>
  <td class=xl74>0.9682</td>
  <td class=xl73>0.9684</td>
  <td class=xl75>0.9684</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9677</td>
  <td class=xl73>0.9682</td>
  <td class=xl74>0.9682</td>
  <td class=xl73>0.9684</td>
  <td class=xl75>0.9684</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9747</td>
  <td class=xl73>0.9800</td>
  <td class=xl74>0.9800</td>
  <td class=xl73>0.9803</td>
  <td class=xl75>0.9803</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

- **Varing Sampling Top k on MultiVAE:yelp:n=100**
<table border=0 cellpadding=0 cellspacing=0 width=1653 style='border-collapse:
 collapse;table-layout:fixed;width:1235pt'>
 <col class=xl65 width=87 span=2 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 span=15 style='width:65pt'>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 width=87 style='height:19.0pt;width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black'>n = 100,
  MultiVAE-yelp,binom</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 100, MultiVAE-yelp,hyper</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 100, MultiVAE-yelp,actual</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>1</td>
  <td class=xl69>0.2574</td>
  <td class=xl69>0.0002</td>
  <td class=xl70>0.2006</td>
  <td class=xl69>0.3111</td>
  <td class=xl71>0.2691</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.2586</td>
  <td class=xl69>0.0002</td>
  <td class=xl70>0.2006</td>
  <td class=xl69>0.3111</td>
  <td class=xl71>0.2691</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.2757</td>
  <td class=xl69>0.0049</td>
  <td class=xl70>0.2154</td>
  <td class=xl69>0.3237</td>
  <td class=xl71>0.2837</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>2</td>
  <td class=xl69>0.4050</td>
  <td class=xl69>0.3129</td>
  <td class=xl70>0.3879</td>
  <td class=xl69>0.4450</td>
  <td class=xl71>0.4194</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.4031</td>
  <td class=xl69>0.3129</td>
  <td class=xl70>0.3879</td>
  <td class=xl69>0.4450</td>
  <td class=xl71>0.4194</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.4137</td>
  <td class=xl69>0.3257</td>
  <td class=xl70>0.3987</td>
  <td class=xl69>0.4550</td>
  <td class=xl71>0.4297</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>5</td>
  <td class=xl69>0.6242</td>
  <td class=xl69>0.6044</td>
  <td class=xl70>0.6308</td>
  <td class=xl69>0.6518</td>
  <td class=xl71>0.6417</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.6241</td>
  <td class=xl69>0.6044</td>
  <td class=xl70>0.6308</td>
  <td class=xl69>0.6518</td>
  <td class=xl71>0.6417</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.6297</td>
  <td class=xl69>0.6104</td>
  <td class=xl70>0.6355</td>
  <td class=xl69>0.6550</td>
  <td class=xl71>0.6455</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>10</td>
  <td class=xl69>0.7748</td>
  <td class=xl69>0.7698</td>
  <td class=xl70>0.7789</td>
  <td class=xl69>0.7853</td>
  <td class=xl71>0.7820</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.7759</td>
  <td class=xl69>0.7698</td>
  <td class=xl70>0.7789</td>
  <td class=xl69>0.7853</td>
  <td class=xl71>0.7820</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.7781</td>
  <td class=xl69>0.7722</td>
  <td class=xl70>0.7812</td>
  <td class=xl69>0.7876</td>
  <td class=xl71>0.7834</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>20</td>
  <td class=xl69>0.8913</td>
  <td class=xl69>0.8902</td>
  <td class=xl70>0.8933</td>
  <td class=xl69>0.8952</td>
  <td class=xl71>0.8941</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8915</td>
  <td class=xl69>0.8902</td>
  <td class=xl70>0.8933</td>
  <td class=xl69>0.8952</td>
  <td class=xl71>0.8941</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8917</td>
  <td class=xl69>0.8909</td>
  <td class=xl70>0.8941</td>
  <td class=xl69>0.8959</td>
  <td class=xl71>0.8950</td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td class=xl72>50</td>
  <td class=xl73>0.9746</td>
  <td class=xl73>0.9752</td>
  <td class=xl74>0.9755</td>
  <td class=xl73>0.9755</td>
  <td class=xl75>0.9755</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9749</td>
  <td class=xl73>0.9752</td>
  <td class=xl74>0.9755</td>
  <td class=xl73>0.9755</td>
  <td class=xl75>0.9755</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9749</td>
  <td class=xl73>0.9754</td>
  <td class=xl74>0.9757</td>
  <td class=xl73>0.9757</td>
  <td class=xl75>0.9756</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

- **Varing Sampling Top k on MultiVAE:yelp:n=1000**

<table border=0 cellpadding=0 cellspacing=0 width=1653 style='border-collapse:
 collapse;table-layout:fixed;width:1235pt'>
 <col class=xl65 width=87 span=2 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 style='mso-width-source:userset;mso-width-alt:2773;
 width:65pt'>
 <col class=xl65 width=87 span=15 style='width:65pt'>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 width=87 style='height:19.0pt;width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
  <td class=xl65 width=87 style='width:65pt'></td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black'>n = 1000,
  MultiVAE-yelp,binom</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 1000, MultiVAE-yelp,hyper</td>
  <td colspan=6 class=xl76 style='border-right:1.0pt solid black;border-left:
  none'>n = 1000, MultiVAE-yelp,actual</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
  <td class=xl66 style='border-left:none'>&nbsp;</td>
  <td class=xl65>SHR</td>
  <td class=xl65>Linear</td>
  <td class=xl67 style='border-top:none'>Bound</td>
  <td class=xl65>Beta@1</td>
  <td class=xl68>Beta@0.5</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>1</td>
  <td class=xl69>0.3049</td>
  <td class=xl69>0.2929</td>
  <td class=xl70>0.3005</td>
  <td class=xl69>0.3111</td>
  <td class=xl71>0.3070</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.3033</td>
  <td class=xl69>0.2929</td>
  <td class=xl70>0.3005</td>
  <td class=xl69>0.3111</td>
  <td class=xl71>0.3070</td>
  <td class=xl66 style='border-left:none'>1</td>
  <td class=xl69>0.3155</td>
  <td class=xl69>0.3059</td>
  <td class=xl70>0.3144</td>
  <td class=xl69>0.3237</td>
  <td class=xl71>0.3193</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>2</td>
  <td class=xl69>0.4433</td>
  <td class=xl69>0.4349</td>
  <td class=xl70>0.4407</td>
  <td class=xl69>0.4450</td>
  <td class=xl71>0.4434</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.4413</td>
  <td class=xl69>0.4349</td>
  <td class=xl70>0.4407</td>
  <td class=xl69>0.4450</td>
  <td class=xl71>0.4434</td>
  <td class=xl66 style='border-left:none'>2</td>
  <td class=xl69>0.4513</td>
  <td class=xl69>0.4458</td>
  <td class=xl70>0.4502</td>
  <td class=xl69>0.4550</td>
  <td class=xl71>0.4528</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>5</td>
  <td class=xl69>0.6488</td>
  <td class=xl69>0.6476</td>
  <td class=xl70>0.6494</td>
  <td class=xl69>0.6518</td>
  <td class=xl71>0.6507</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.6495</td>
  <td class=xl69>0.6476</td>
  <td class=xl70>0.6494</td>
  <td class=xl69>0.6518</td>
  <td class=xl71>0.6507</td>
  <td class=xl66 style='border-left:none'>5</td>
  <td class=xl69>0.6519</td>
  <td class=xl69>0.6511</td>
  <td class=xl70>0.6533</td>
  <td class=xl69>0.6550</td>
  <td class=xl71>0.6543</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>10</td>
  <td class=xl69>0.7854</td>
  <td class=xl69>0.7838</td>
  <td class=xl70>0.7846</td>
  <td class=xl69>0.7853</td>
  <td class=xl71>0.7850</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.7851</td>
  <td class=xl69>0.7838</td>
  <td class=xl70>0.7846</td>
  <td class=xl69>0.7853</td>
  <td class=xl71>0.7850</td>
  <td class=xl66 style='border-left:none'>10</td>
  <td class=xl69>0.7869</td>
  <td class=xl69>0.7862</td>
  <td class=xl70>0.7869</td>
  <td class=xl69>0.7876</td>
  <td class=xl71>0.7872</td>
 </tr>
 <tr height=24 style='height:18.0pt'>
  <td height=24 class=xl65 style='height:18.0pt'></td>
  <td class=xl66>20</td>
  <td class=xl69>0.8952</td>
  <td class=xl69>0.8948</td>
  <td class=xl70>0.8950</td>
  <td class=xl69>0.8952</td>
  <td class=xl71>0.8951</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8949</td>
  <td class=xl69>0.8948</td>
  <td class=xl70>0.8950</td>
  <td class=xl69>0.8952</td>
  <td class=xl71>0.8951</td>
  <td class=xl66 style='border-left:none'>20</td>
  <td class=xl69>0.8960</td>
  <td class=xl69>0.8954</td>
  <td class=xl70>0.8956</td>
  <td class=xl69>0.8959</td>
  <td class=xl71>0.8957</td>
 </tr>
 <tr height=25 style='height:19.0pt'>
  <td height=25 class=xl65 style='height:19.0pt'></td>
  <td class=xl72>50</td>
  <td class=xl73>0.9754</td>
  <td class=xl73>0.9755</td>
  <td class=xl74>0.9755</td>
  <td class=xl73>0.9755</td>
  <td class=xl75>0.9755</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9756</td>
  <td class=xl73>0.9755</td>
  <td class=xl74>0.9755</td>
  <td class=xl73>0.9755</td>
  <td class=xl75>0.9755</td>
  <td class=xl72 style='border-left:none'>50</td>
  <td class=xl73>0.9759</td>
  <td class=xl73>0.9756</td>
  <td class=xl74>0.9757</td>
  <td class=xl73>0.9757</td>
  <td class=xl75>0.9757</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

## 2. Mapping Functions Comparison (table 5)
**MultiVAE:ml-1m**
<table border=0 cellpadding=0 cellspacing=0 width=609 style='border-collapse:
 collapse;table-layout:fixed;width:455pt'>
 <col class=xl69 width=87 span=7 style='width:65pt'>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 style='height:16.0pt'>&nbsp;</td>
  <td colspan=6 class=xl66 style='border-left:none'>MultiVAE:ml-1m</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 style='height:16.0pt;border-top:none'>&nbsp;</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@2-10</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@2-10</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Linear</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0058</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0226</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0992</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9934</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0391</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1238</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Bound</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0024</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0103</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0596</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5970</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0100</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0363</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@1</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0034</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0074</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0118</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1177</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0165</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0440</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.5</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0019</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0043</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0169</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1692</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0052</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0112</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.2</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0018</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0065</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0356</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3566</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0060</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0207</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@P</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0018</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0052</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0250</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2504</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0052</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0146</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

**NeuMF:yelp**

<table border=0 cellpadding=0 cellspacing=0 width=609 style='border-collapse:
 collapse;table-layout:fixed;width:455pt'>
 <col class=xl65 width=87 span=8 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 style='height:16.0pt'>&nbsp;</td>
  <td colspan=6 class=xl66 style='border-left:none'>NeuMF:yelp</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 style='height:16.0pt;border-top:none'>&nbsp;</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@2-10</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@2-10</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Linear</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0057</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0164</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2329</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9886</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0300</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0632</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Bound</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0019</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0046</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0606</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2571</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0061</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0125</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@1</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0038</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0070</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0414</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1756</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0221</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0413</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.5</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0020</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0030</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0032</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0134</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0112</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0197</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.2</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0015</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0027</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0253</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1075</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0057</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0097</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@P</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0015</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0024</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0145</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0617</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0067</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0106</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

- **EASE:ml-1m**
<table border=0 cellpadding=0 cellspacing=0 width=609 style='border-collapse:
 collapse;table-layout:fixed;width:455pt'>
 <col class=xl69 width=87 span=7 style='width:65pt'>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 width=87 style='height:16.0pt;width:65pt'>&nbsp;</td>
  <td colspan=6 class=xl66 width=522 style='border-left:none;width:390pt'>EASE:ml-1m</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 style='height:16.0pt;border-top:none'>&nbsp;</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@2-10</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@2-10</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Linear</td>
  <td class=xl72>
  <!doctype>
  0.0056</td>
  <td class=xl67 style='border-top:none'>0.0211</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1101</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9666</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0374</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1118</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Bound</td>
  <td class=xl72>0.0025</td>
  <td class=xl67 style='border-top:none'>0.0084</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0500</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4390</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0092</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0294</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@1</td>
  <td class=xl72>0.0037</td>
  <td class=xl67 style='border-top:none'>0.0081</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0205</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1802</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0152</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0408</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.5</td>
  <td class=xl72>0.0019</td>
  <td class=xl67 style='border-top:none'>0.0031</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0055</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0480</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0040</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0085</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.2</td>
  <td class=xl72>0.0018</td>
  <td class=xl67 style='border-top:none'>0.0047</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0237</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2078</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0047</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0137</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@P</td>
  <td class=xl72>0.0017</td>
  <td class=xl67 style='border-top:none'>0.0034</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0141</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1235</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0027</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0059</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

- **itemKNN-yelp**
<table border=0 cellpadding=0 cellspacing=0 width=609 style='border-collapse:
 collapse;table-layout:fixed;width:455pt'>
 <col class=xl65 width=87 span=8 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 width=87 style='height:16.0pt;width:65pt'>&nbsp;</td>
  <td colspan=6 class=xl66 width=522 style='border-left:none;width:390pt'>itemKNN:yelp</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl70 style='height:16.0pt;border-top:none'>&nbsp;</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@1</td>
  <td class=xl66 style='border-top:none;border-left:none'>abs@2-10</td>
  <td class=xl66 style='border-top:none;border-left:none'>rel@2-10</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Linear</td>
  <td class=xl68 style='border-top:none;border-left:none'>
  <!doctype>
  0.0057</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0145</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3019</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9874</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0240</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0443</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Bound</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0019</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0035</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0529</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1731</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0053</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0086</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@1</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0040</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0069</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0612</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2003</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0230</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0384</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.5</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0024</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0036</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0183</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0599</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0131</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0212</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@0.2</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0015</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0022</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0113</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0369</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0067</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0101</td>
 </tr>
 <tr height=21 style='height:16.0pt'>
  <td height=21 class=xl71 style='height:16.0pt;border-top:none'>Beta@P</td>
  <td class=xl68 style='border-top:none;border-left:none'>0.0017</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0023</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0023</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0075</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0086</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.0135</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>


## 3. Predicting Winners(and Relative Performance) (table 6)

- **ml-1m**
<table border=0 cellpadding=0 cellspacing=0 width=1218 style='border-collapse:
 collapse;table-layout:fixed;width:910pt'>
 <col class=xl65 width=87 span=14 style='width:65pt'>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66>ml-1m</td>
  <td colspan=3 class=xl66 style='border-left:none'>NeuMF</td>
  <td colspan=3 class=xl66 style='border-left:none'>MultiVAE</td>
  <td colspan=3 class=xl66 style='border-left:none'>EASE</td>
  <td colspan=3 class=xl66 style='border-left:none'>ALS</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>k</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>1</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2081</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1502</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2058</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2119</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1608</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2161</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2233</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1737</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2326</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2136</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1606</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2242</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>2</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3268</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3119</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3470</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3430</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3199</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3555</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3497</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3348</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3700</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3329</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3205</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3508</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>5</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5485</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5555</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5669</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5558</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5603</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5768</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5646</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5732</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5873</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5339</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5452</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5566</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>10</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7156</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7263</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7313</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7177</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7295</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7334</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7207</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7339</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7374</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6942</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7053</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7093</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>20</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8508</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8639</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8646</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8545</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8661</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8674</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8477</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8594</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8604</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8225</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8364</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8374</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>50</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9722</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9790</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9790</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9725</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9800</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9798</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9555</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9618</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9616</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9315</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9364</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9364</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

- **yelp**
<table border=0 cellpadding=0 cellspacing=0 width=1218 style='border-collapse:
 collapse;table-layout:fixed;width:910pt'>
 <col class=xl65 width=87 span=14 style='width:65pt'>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66>yelp</td>
  <td colspan=3 class=xl66 style='border-left:none'>NeuMF</td>
  <td colspan=3 class=xl66 style='border-left:none'>MultiVAE</td>
  <td colspan=3 class=xl66 style='border-left:none'>EASE</td>
  <td colspan=3 class=xl66 style='border-left:none'>ALS</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>k</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>1</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2346</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1846</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2488</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2623</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2154</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2837</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2751</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2284</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2953</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2467</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1990</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2597</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>2</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3697</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3600</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3921</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4049</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3987</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4297</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4181</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4105</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4423</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3782</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3698</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3968</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>5</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5934</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6009</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6114</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6263</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6355</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6455</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6328</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6426</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6538</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5734</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5826</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5917</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>10</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7537</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7606</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7640</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7751</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7812</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7834</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7770</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7842</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7878</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7025</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7049</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7081</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>20</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8814</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8854</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8862</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8922</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8941</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8950</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8867</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8889</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8894</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7972</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7994</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7999</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>50</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9756</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9762</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9762</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9745</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9757</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9756</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9574</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9578</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9577</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8756</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8759</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8758</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

- **pinterest-20**

<table border=0 cellpadding=0 cellspacing=0 width=1442 style='border-collapse:
 collapse;table-layout:fixed;width:1078pt'>
 <col class=xl65 width=103 span=14 style='width:77pt'>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66>pinterest-20</td>
  <td colspan=3 class=xl66 style='border-left:none'>NeuMF</td>
  <td colspan=3 class=xl66 style='border-left:none'>MultiVAE</td>
  <td colspan=3 class=xl66 style='border-left:none'>EASE</td>
  <td colspan=3 class=xl66 style='border-left:none'>ALS</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>k</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>1</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2734</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2019</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2780</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3106</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2417</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3219</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2899</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2223</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2981</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2623</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.1972</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2651</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>2</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4360</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4095</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4489</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4792</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4560</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4950</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4529</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4275</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4656</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4158</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3903</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4269</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>5</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7010</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7080</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7221</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7296</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7351</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7477</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7057</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7120</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7248</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6659</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6706</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6833</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>10</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8741</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8832</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8866</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8876</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8948</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8977</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8688</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8776</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8807</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8298</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8381</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8416</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>20</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9651</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9685</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9688</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9706</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9737</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9739</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9596</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9633</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9637</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9233</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9269</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9272</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>50</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9935</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9934</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9934</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9946</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9947</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9947</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9891</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9894</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9893</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9582</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9584</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9583</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
  <td width=103 style='width:77pt'></td>
 </tr>
 <![endif]>
</table>

- **citeulike**
<table border=0 cellpadding=0 cellspacing=0 width=1218 style='border-collapse:
 collapse;table-layout:fixed;width:910pt'>
 <col class=xl65 width=87 span=14 style='mso-width-source:userset;mso-width-alt:
 2773;width:65pt'>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66><span style='mso-spacerun:yes'></span>citeulike</td>
  <td colspan=3 class=xl66 style='border-left:none'>NeuMF</td>
  <td colspan=3 class=xl66 style='border-left:none'>MultiVAE</td>
  <td colspan=3 class=xl66 style='border-left:none'>EASE</td>
  <td colspan=3 class=xl66 style='border-left:none'>ALS</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>K</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
  <td class=xl66 style='border-top:none;border-left:none'>SHR</td>
  <td class=xl66 style='border-top:none;border-left:none'>Bound</td>
  <td class=xl66 style='border-top:none;border-left:none'>Beta@0.5</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>1</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3994</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4277</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5059</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4886</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5545</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6157</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4648</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5118</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5779</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2801</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.2508</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.3122</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>2</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.5837</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6069</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6325</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6756</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7074</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7271</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6411</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6745</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6970</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4208</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4174</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.4460</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>5</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7674</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7748</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7838</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8285</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8398</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8458</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8024</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8117</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8150</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6193</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6269</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.6374</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>10</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8717</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8780</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8800</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9108</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9142</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9161</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8804</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8860</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8876</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7620</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7678</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.7696</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>20</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9407</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9442</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9447</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9613</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9629</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9631</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9342</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9360</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9362</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8694</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8707</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.8714</td>
 </tr>
 <tr height=27 style='mso-height-source:userset;height:20.0pt'>
  <td height=27 class=xl65 style='height:20.0pt'></td>
  <td class=xl66 style='border-top:none'>50</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9870</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9876</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9876</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9924</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9919</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9919</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9690</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9688</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9688</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9600</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9584</td>
  <td class=xl67 style='border-top:none;border-left:none'>0.9580</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
  <td width=87 style='width:65pt'></td>
 </tr>
 <![endif]>
</table>

