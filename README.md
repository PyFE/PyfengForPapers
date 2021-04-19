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
* [Py Notebook](ipynb/ChoiWu2021-QF-NoteOnMassZero.ipynb) | Choi, J., & Wu, L. (2021). A note on the option price and ‘Mass at zero in the uncorrelated SABR model and implied volatility asymptotics.’ Quantitative Finance (Forthcoming). https://doi.org/10.1080/14697688.2021.1876908 
* [Py Notebook](ipynb/ChoiEtAl2021-BachlierModel.ipynb) | Choi, J. et al. (2021). A Black-Scholes user's guide to the Bachelier model. Working Paper.
* [Py Notebook](ipynb/KrekelEtAl2004-Wilmott-BasketOption.ipynb) (partially implemented) : Krekel, M., de Kock, J., Korn, R., & Man, T.-K. (2004). An analysis of pricing methods for basket options. Wilmott Magazine, 2004(7), 82–89.
* [Py Notebook](ipynb/AntonovEtAl-2012-SSRN-SABR.ipynb) | Several SABR Model papers by Antonov and co-authors.
  * Antonov, A., & Spector, M. (2012). Advanced analytics for the SABR model. Available at SSRN. https://ssrn.com/abstract=2026350 
  * Antonov, A., Konikov, M., & Spector, M. (2013). SABR spreads its wings. Risk, 2013(Aug), 58–63.
  * Antonov, A., Konikov, M., & Spector, M. (2019). Modern SABR Analytics. Springer International Publishing. https://doi.org/10.1007/978-3-030-10656-0
* [Py Notebook](ipynb/ChoiEtAl2019-Fut-NSVh.ipynb) | Choi, J., Liu, C., & Seo, B. K. (2019). Hyperbolic normal stochastic volatility model. Journal of Futures Markets, 39(2), 186–204. https://doi.org/10.1002/fut.21967
