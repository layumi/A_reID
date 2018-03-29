# A_reID

### Method-ID
1. Fast [1]
2. Basic Iteration [2]
3. Least-likly Iteration [3] 
4. Label-smooth 
5. Our 

Only attack query. 
### ResNet-50
|Rate  | Method-ID | top-1 | top-5 | top-10 | mAP|
| ---- | --------- | ----- | ----- | ------ | -- |
|2 | 1 | 0.818587 | 0.920724 | 0.950416 | 0.623365 |
|2 | 2 | 0.813539 | 0.917458 | 0.948337 | 0.617632 |
|2 | 3 | 0.838480 | 0.929632 | 0.956057 | 0.639190 |
|2 | 4 | 0.855701 | 0.941508 | 0.962292 | 0.656828 |
|2 | 4(L1Loss) | 0.856591 | 0.942399 | 0.963777 | 0.657387 |
|2 | 5 | 0.824525 | 0.930523 | 0.954869 | 0.638534 |
|2 | 5(L1Loss) | 0.852138 | 0.943587 | 0.961698 | 0.676618 |
|4 | 1 | 0.668943 | 0.826900 | 0.875000 | 0.472484 |
|4 | 2 | 0.512767 | 0.694774 | 0.766924 | 0.349721 |
|4 | 3 | 0.611639 | 0.771972 | 0.828385 | 0.411155 |
|4 | 4 | 0.784145 | 0.903800 | 0.938539 | 0.558413 |
|4 | 4(L1Loss) | 0.786817 | 0.906176 | 0.940024 | 0.561066 |
|4 | 5 | 0.438836 | 0.612530 | 0.692102 | 0.304175 |
|4 | 5(L1Loss) | 0.747625 | 0.883017 | 0.922209 | 0.567336 |
|8 | 1 | 0.387470 | 0.572150 | 0.647862 | 0.251643 |
|8 | 2 | 0.237827 | 0.401722 | 0.496437 | 0.154831 |
|8 | 3 | 0.233967 | 0.380048 | 0.450416 | 0.136701 |
|8 | 4 | 0.695368 | 0.856888 | 0.899050 | 0.456100 | 
|8 | 4(L1Loss) | 0.696556 | 0.860451 | 0.899941 | 0.459463 |
|8 | 5 | 0.078682 | 0.156770 | 0.209917 | 0.057566 |
|8 | 5(L1Loss) | 0.536520 | 0.726544 | 0.793646 | 0.389121 |
|12 | 1 | 0.194181 | 0.339667 | 0.409442 | 0.125345 |
|12 | 2 | 0.139252 | 0.277613 | 0.359264 | 0.096759 |
|12 | 3 | 0.088777 | 0.167458 | 0.217637 | 0.052525 |
|12 | 4 | 0.638064 | 0.812055 | 0.864311 | 0.397876 |
|12 | 4(L1Loss) | 0.638064 | 0.818290 | 0.864608 | 0.398857 |
|12 | 5 | 0.020487 | 0.044240 | 0.062055 | 0.015395 |
|12 | 5(L1Loss) | 0.369952 | 0.557304 | 0.645784 | 0.270214 |
|16 | 1 | 0.085808 | 0.176366 | 0.223575 | 0.057531 |
|16 | 2 | 0.094418 | 0.222387 | 0.298100 | 0.071568 |
|16 | 3 | 0.037411 | 0.087886 | 0.120249 | 0.025099 |
|16 | 4 | 0.596200 | 0.779988 | 0.842340 | 0.356884 |
|16 | 4(L1Loss) | 0.588480 | 0.781473 | 0.843230 | 0.358868 |
|16 | 5 | 0.005344 | 0.016033 | 0.023753 | 0.006218 |
|16 | 5(L1Loss) | 0.264549 | 0.430226 | 0.514252 | 0.196718 |

### Reference
[1] I. J. Goodfellow, J. Shlens, and C. Szegedy. Explaining and harnessing adversarial examples. In ICLR, 2015

[2] C. Szegedy, W. Zaremba, I. Sutskever, J. Bruna, D. Erhan, I. J. Goodfellow, and R. Fergus. Intriguing properties of
neural networks. In ICLR, 2014.

[3] A. Kurakin, I. J. Goodfellow, & S. Bengio. (2016). Adversarial examples in the physical world. In ICLR Workshop, 2017.
