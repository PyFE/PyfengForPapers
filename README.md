# PyfengForPapers
PyfengForPapers hosts a collection of the Py notebooks (`.ipynb`) that use [`PyFENG`](https://pypi.org/project/pyfeng) package to reproduce the results of financial engineering papers. This repository aims to help researchers by providing a replication for published papers. The installation of [`PyFENG`](https://pypi.org/project/pyfeng) is required.

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
  * Make a local copy of [PyFENG repository](https://github.com/PyFE/PyFENG/) by forking or download.
  * Make necessary modifications.
  * Uncomment the following lines in the beginning of notebook file. Then, the local `PyFENG` will be used.
    ```py
    %load_ext autoreload
    %autoreload 2
    ```
    ``` py
    import sys
    sys.path.insert(sys.path.index('')+1, 'PATH_TO_LOCAL_PYFENG')
    ```

## List of Implemented Papers 
* [Notebook](ipynb/ChoiEtAl2025-Tighter-BSIV-Bounds.ipynb) | Choi J, Huh J & Su N (2025). __Tighter 'Uniform Bounds for Black-Scholes Implied Volatility' and the applications to root-finding.__ [[arXiv](https://arxiv.org/abs/2302.08758)]
* [Notebook](ipynb/ChoiSeo2023-SabrNorm-GaussQuad.ipynb) | Choi J & Seo BK (2023). __Option pricing under the normal SABR model with Gaussian quadratures.__ [[arXiv](https://arxiv.org/abs/2301.02797)]
* [Notebook](ipynb/ChoiChen2022-JDQS-RiskParity.ipynb) | Choi J & Chen R (2022). __Improved iterative methods for solving risk parity portfolio.__ _Journal of Derivatives and Quantitative Studies_, 30(2), 114-124. DOI:[10.1108/JDQS-12-2021-0031](https://doi.org/10.1108/JDQS-12-2021-0031) (Open Access) [[arXiv](https://arxiv.org/abs/2203.00148)].
* [Notebook](ipynb/ChoiEtAl2022-Fut-BachelierModel.ipynb) | Choi J et al. (2022). __A Black-Scholes user's guide to the Bachelier model.__ _Journal of Futures Markets_, 42(5), 959-980. DOI:[10.1002/fut.22315](https://doi.org/10.1002/fut.22315) [[arXiv](https://arxiv.org/abs/2104.08686)]
* [Notebook](ipynb/ChoiWu2021-QF-NoteOnMassZero.ipynb) | Choi J & Wu L (2021). __A note on the option price and 'Mass at zero in the uncorrelated SABR model and implied volatility asymptotics.'__ _Quantitative Finance_, 21, 1083. DOI:[10.1080/14697688.2021.1876908](https://doi.org/10.1080/14697688.2021.1876908) [[arXiv](https://arxiv.org/abs/2011.00557)]
* [Notebook](ipynb/ChoiWu2021-JEDC-SABR-CEV.ipynb) | Choi J & Wu L (2021). The equivalent constant-elasticity-of-variance (CEV) volatility of the stochastic-alpha-beta-rho (SABR) model. _Journal of Economic Dynamics and Control_, 128, 104143. DOI:[10.1016/j.jedc.2021.104143](https://doi.org/10.1016/j.jedc.2021.104143) [[arXiv](https://arxiv.org/abs/1911.13123)]
* [Notebook](ipynb/KrekelEtAl2004-Wilmott-BasketOption.ipynb) | Krekel M, de Kock J, Korn R, & Man TK (2004). An analysis of pricing methods for basket options. _Wilmott Magazine_, 2004(7), 82–89.
* [Notebook](ipynb/AntonovEtAl-2012-SSRN-SABR.ipynb) | Several SABR Model papers by Antonov and co-authors.
  * Antonov A, & Spector M (2012). Advanced analytics for the SABR model. [[SSRN](https://ssrn.com/abstract=2026350)] 
  * Antonov A, Konikov M, & Spector M (2013). SABR spreads its wings. _Risk_, 2013(Aug), 58–63.
  * Antonov A, Konikov M, & Spector M (2019). Modern SABR Analytics. Springer International Publishing. DOI:[10.1007/978-3-030-10656-0](https://doi.org/10.1007/978-3-030-10656-0)
* [Notebook](ipynb/ChoiEtAl2019-Fut-NSVh.ipynb) | Choi J, Liu C, & Seo BK. (2019). Hyperbolic normal stochastic volatility model. _Journal of Futures Markets_, 39(2), 186–204. DOI:[10.1002/fut.21967](https://doi.org/10.1002/fut.21967) [[arXiv](https://arxiv.org/abs/1809.04035)]
* [Notebook](ipynb/BallRoma1994-JFQA-Heston.ipynb) | Ball CA, Roma A (1994). __Stochastic Volatility Option Pricing.__ _Journal of Financial and Quantitative Analysis_ 29:589–607. DOI:[10.2307/2331111](https://doi.org/10.2307/2331111)
* [Notebook](ipynb/SchobelZhu1999-RF-OUSV.ipynb) | Schöbel R, Zhu J (1999). __Stochastic Volatility With an Ornstein–Uhlenbeck Process: An Extension.__ _Review of Finance_ 3:23–46. DOI:[10.1023/A:1009803506170](https://doi.org/10.1023/A:1009803506170)
* Coming Soon | Choi J (2018). __Sum of all Black-Scholes-Merton models: An efficient pricing method for spread, basket, and Asian options.__ _Journal of Futures Markets_, 38:627–644. DOI:[10.1002/fut.21909](https://doi.org/10.1002/fut.21909)
* [Notebook](ipynb/BaroneAdesiEtAl2005-CSDA-UncorGarch.ipynb) | Barone-Adesi G, Rasmussen H, Ravanelli C (2005). __An option pricing formula for the GARCH diffusion model.__ _Computational Statistics & Data Analysis_ 49:287–310. DOI:[10.1016/j.csda.2004.05.014](https://doi.org/10.1016/j.csda.2004.05.014)
* [Notebook](ipynb/Baldeaux2012-Sv32-ExactMC.ipynb) | Baldeaux J (2012). __Exact simulation of the 3/2 model.__ _International Journal of Theoretical and Applied Finance_, 15:1250032. DOI:[10.1142/S021902491250032X](https://doi.org/10.1142/S021902491250032X)
