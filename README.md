Labs for Statistics and Machine Learning in Python
=================================================

Centralize, clone nice ressources to perform labs for [pystatsml](https://github.com/duchesnay/pystatsml)
 
Links

- [pystatsml github](https://github.com/duchesnay/pystatsml)
- [pdf](https://raw.github.com/duchesnay/data/master/pdf/StatisticsMachineLearningPython.pdf)
- [www](https://duchesnay.github.io/pystatsml)




Python for Finance (2nd ed.)
----------------------------

**Mastering Data-Driven Finance**

&copy; Dr. Yves J. Hilpisch | The Python Quants GmbH

<img src="http://hilpisch.com/images/py4fi_2nd_shadow.png" width="300px" align="left">

- [Simulation and Stochastic Processes](py4fi_book/code/12_stochastics.ipynb)




Installation using pixi
-----------------------

Install [Pixi](https://pixi.sh/latest/)

Linux & macOS

```
curl -fsSL https://pixi.sh/install.sh | bash
```

Windows

```
iwr -useb https://pixi.sh/install.ps1 | iex
```

```
git clone https://github.com/duchesnay/pystatsml_labs.git
cd pystatsml_labs
pixi install
pixi shell
```

Initial creation of the environement using pixi
-----------------------------------------------

```
pixi init pystatsml_labs
cd pystatsml_labs
pixi add python=3.8 ipykernel
pixi add scikit-learn scipy pandas statsmodels seaborn
pixi add nbstripout
```

Configure your git repository with `nbstripout`: a pre-commit hook for users who don't want to track notebooks' outputs in git.

```
nbstripout --install
```

