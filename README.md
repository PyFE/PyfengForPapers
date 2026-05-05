# PyfengForPapers
PyfengForPapers hosts a collection of the Py notebooks (`.ipynb`) that use [`PyFENG`](https://pypi.org/project/pyfeng) package to reproduce the results of financial engineering papers. This repository aims to help researchers by providing a replication for published papers. [`PyFENG`](https://pypi.org/project/pyfeng) is installed in CoLab. Or ee [PyFENG Installation](#pyfeng-installation) below for local installation.

## List of Implemented Papers 
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/Choi2025-ORL-OusvMC.ipynb) [ipynb/Choi2025-ORL-OusvMC.ipynb](ipynb/Choi2025-ORL-OusvMC.ipynb)
  * Choi J (2025) __Exact simulation scheme for the Ornstein–Uhlenbeck driven stochastic volatility model with the Karhunen–Loève expansions.__ _Operations Research Letters_, 60:107280 [[DOI](https://doi.org/10.1016/j.orl.2025.107280) | [arXiv](https://arxiv.org/abs/2402.09243) | [SSRN](https://ssrn.com/abstract=4726506)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiHuhSu2024-Tighter-BSIV-Bounds.ipynb) [ipynb/ChoiHuhSu2024-Tighter-BSIV-Bounds.ipynb](ipynb/ChoiHuhSu2024-Tighter-BSIV-Bounds.ipynb)
  * Choi J, Huh J & Su N (2024). __Tighter ‘uniform bounds for Black–Scholes implied volatility’ and the applications to root-finding.__ _Operations Research Letters_, 57, 107189 [[DOI](https://doi.org/10.1016/j.orl.2024.107189) | [arXiv](https://arxiv.org/abs/2302.08758) | [SSRN](https://ssrn.com/abstract=4362251)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiSeo2023-SabrNorm-GaussQuad.ipynb) [ipynb/ChoiSeo2023-SabrNorm-GaussQuad.ipynb](ipynb/ChoiSeo2023-SabrNorm-GaussQuad.ipynb)
  * Choi J & Seo BK (2024). __Option pricing under the normal SABR model with Gaussian quadratures.__ _Journal of Computational Finance_, 28(2), 1-20 [[DOI](https://doi.org/10.21314/JCF.2024.007) | [arXiv](https://arxiv.org/abs/2301.02797) | [SSRN](https://ssrn.com/abstract=4265261)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/Choi2023-Talk-Bloomberg.ipynb) [ipynb/Choi2023-Talk-Bloomberg.ipynb](ipynb/Choi2023-Talk-Bloomberg.ipynb)
  * Choi J (2023). __Equivalent CEV Volatility.__ Bloomberg Quant Seminar.
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiChen2022-JDQS-RiskParity.ipynb) [ipynb/ChoiChen2022-JDQS-RiskParity.ipynb](ipynb/ChoiChen2022-JDQS-RiskParity.ipynb)
  * Choi J & Chen R (2022). __Improved iterative methods for solving risk parity portfolio.__ _Journal of Derivatives and Quantitative Studies_, 30(2), 114-124 [[DOI](https://doi.org/10.1108/JDQS-12-2021-0031) | [arXiv](https://arxiv.org/abs/2203.00148) | [SSRN](https://ssrn.com/abstract=4045631)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiEtAl2022-Fut-BachelierModel.ipynb) [ipynb/ChoiEtAl2022-Fut-BachelierModel.ipynb](ipynb/ChoiEtAl2022-Fut-BachelierModel.ipynb)
  * Choi J et al. (2022). __A Black-Scholes user’s guide to the Bachelier model.__ _Journal of Futures Markets_, 42(5), 959-980 [[DOI](https://doi.org/10.1002/fut.22315) | [arXiv](https://arxiv.org/abs/2104.08686) | [SSRN](https://ssrn.com/abstract=3828310)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiWu2021-QF-NoteOnMassZero.ipynb) [ipynb/ChoiWu2021-QF-NoteOnMassZero.ipynb](ipynb/ChoiWu2021-QF-NoteOnMassZero.ipynb)
  * Choi J & Wu L (2021). __A note on the option price and ‘Mass at zero in the uncorrelated SABR model and implied volatility asymptotics.’__ _Quantitative Finance_, 21, 1083 [[DOI](https://doi.org/10.1080/14697688.2021.1876908) | [arXiv](https://arxiv.org/abs/2011.00557) | [SSRN](https://ssrn.com/abstract=3709778)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiWu2021-JEDC-SABR-CEV.ipynb) [ipynb/ChoiWu2021-JEDC-SABR-CEV.ipynb](ipynb/ChoiWu2021-JEDC-SABR-CEV.ipynb)
  * Choi J & Wu L (2021). The equivalent constant-elasticity-of-variance (CEV) volatility of the stochastic-alpha-beta-rho (SABR) model. _Journal of Economic Dynamics and Control_, 128, 104143 [[DOI](https://doi.org/10.1016/j.jedc.2021.104143) | [arXiv](https://arxiv.org/abs/1911.13123) | [SSRN](https://ssrn.com/abstract=3495464)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoiEtAl2019-Fut-NSVh.ipynb) [ipynb/ChoiEtAl2019-Fut-NSVh.ipynb](ipynb/ChoiEtAl2019-Fut-NSVh.ipynb)
  * Choi J, Liu C, & Seo BK. (2019). Hyperbolic normal stochastic volatility model. _Journal of Futures Markets_, 39(2), 186–204 [[DOI](https://doi.org/10.1002/fut.21967) | [arXiv](https://arxiv.org/abs/1809.04035) | [SSRN](https://ssrn.com/abstract=3068836)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/BernardCui2014-DiscreteVarianceSwap.ipynb) [ipynb/BernardCui2014-DiscreteVarianceSwap.ipynb](ipynb/BernardCui2014-DiscreteVarianceSwap.ipynb)
  * Bernard C, Cui Z (2014). __Prices and Asymptotics for Discrete Variance Swaps.__ _Applied Mathematical Finance_, 21(2), 140-173 [[DOI](https://doi.org/10.1080/1350486X.2013.820524) | [arXiv](https://arxiv.org/abs/1305.7092)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/AntonovEtAl-2012-SSRN-SABR.ipynb) [ipynb/AntonovEtAl-2012-SSRN-SABR.ipynb](ipynb/AntonovEtAl-2012-SSRN-SABR.ipynb)
  * Several SABR Model papers by Antonov and co-authors.
  * Antonov A, & Spector M (2012). Advanced analytics for the SABR model [[SSRN](https://ssrn.com/abstract=2026350)]
  * Antonov A, Konikov M, & Spector M (2013). SABR spreads its wings. _Risk_, 2013(Aug), 58–63
  * Antonov A, Konikov M, & Spector M (2019). Modern SABR Analytics. Springer International Publishing [[DOI](https://doi.org/10.1007/978-3-030-10656-0)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/Baldeaux2012-Sv32-ExactMC.ipynb) [ipynb/Baldeaux2012-Sv32-ExactMC.ipynb](ipynb/Baldeaux2012-Sv32-ExactMC.ipynb)
  * Baldeaux J (2012). __Exact simulation of the 3/2 model.__ _International Journal of Theoretical and Applied Finance_, 15:1250032 [[DOI](https://doi.org/10.1142/S021902491250032X) | [arXiv](https://arxiv.org/abs/1105.3297)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/WuMaWang2012-EconModel-GarchFFT.ipynb) [ipynb/WuMaWang2012-EconModel-GarchFFT.ipynb](ipynb/WuMaWang2012-EconModel-GarchFFT.ipynb)
  * Wu X-Y, Ma C-Q, Wang S-Y (2012). __Warrant pricing under GARCH diffusion model.__ _Economic Modelling_, 29:2237-2244 [[DOI](https://doi.org/10.1016/j.econmod.2012.06.020)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/KrekelEtAl2004-Wilmott-BasketOption.ipynb) [ipynb/KrekelEtAl2004-Wilmott-BasketOption.ipynb](ipynb/KrekelEtAl2004-Wilmott-BasketOption.ipynb)
  * Krekel M, de Kock J, Korn R, & Man TK (2004). An analysis of pricing methods for basket options. _Wilmott Magazine_, 2004(7), 82–89
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/BaroneAdesiEtAl2005-CSDA-GarchUncorr.ipynb) [ipynb/BaroneAdesiEtAl2005-CSDA-GarchUncorr.ipynb](ipynb/BaroneAdesiEtAl2005-CSDA-GarchUncorr.ipynb)
  * Barone-Adesi G, Rasmussen H, Ravanelli C (2005). __An option pricing formula for the GARCH diffusion model.__ _Computational Statistics & Data Analysis_ 49:287–310 [[DOI](https://doi.org/10.1016/j.csda.2004.05.014)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/BallRoma1994-JFQA-Heston.ipynb) [ipynb/BallRoma1994-JFQA-Heston.ipynb](ipynb/BallRoma1994-JFQA-Heston.ipynb)
  * Ball CA, Roma A (1994). __Stochastic Volatility Option Pricing.__ _Journal of Financial and Quantitative Analysis_ 29:589–607 [[DOI](https://doi.org/10.2307/2331111)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/SchobelZhu1999-RF-OUSV.ipynb) [ipynb/SchobelZhu1999-RF-OUSV.ipynb](ipynb/SchobelZhu1999-RF-OUSV.ipynb)
  * Schöbel R, Zhu J (1999). __Stochastic Volatility With an Ornstein–Uhlenbeck Process: An Extension.__ _Review of Finance_ 3:23–46 [[DOI](https://doi.org/10.1023/A:1009803506170)]
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyFE/PyfengForPapers/blob/main/ipynb/ChoudhuryLucantoni1996-OR-MGFtoMoments.ipynb) [ipynb/ChoudhuryLucantoni1996-OR-MGFtoMoments.ipynb](ipynb/ChoudhuryLucantoni1996-OR-MGFtoMoments.ipynb)
  * Choudhury GL, Lucantoni DM (1996). __Numerical Computation of the Moments of a Probability Distribution from its Transform.__ _Operations Research_, 44:368-381 [[DOI](https://doi.org/10.1287/opre.44.2.368)]
* Coming Soon
  * Choi J (2018). __Sum of all Black-Scholes-Merton models: An efficient pricing method for spread, basket, and Asian options.__ _Journal of Futures Markets_, 38:627–644 [[DOI](https://doi.org/10.1002/fut.21909) | [arXiv](https://arxiv.org/abs/1805.03172) | [SSRN](https://ssrn.com/abstract=2913048)]

## `PyFENG` Installation
* For the first-time installation,
  ```sh
  pip install pyfeng
  ```
* For an upgrade,
  ```sh
  pip install --upgrade pyfeng
  ```
* If running on your modified implementation, 
  * Make a local copy of [PyFENG repository](https://github.com/PyFE/PyFENG/) by forking or download
  * Make necessary modifications
  * Uncomment the following lines in the beginning of notebook file. Then, the local `PyFENG` will be used
    ```py
    %load_ext autoreload
    %autoreload 2
    ```
    ``` py
    import sys
    sys.path.insert(sys.path.index('')+1, 'PATH_TO_LOCAL_PYFENG')
    ```
