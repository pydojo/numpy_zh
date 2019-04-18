# <img alt="NumPy" src="https://cdn.rawgit.com/numpy/numpy/master/branding/icons/numpylogo.svg" height="60">

[![Travis](https://img.shields.io/travis/numpy/numpy/master.svg?label=Travis%20CI)](
    https://travis-ci.org/numpy/numpy)
[![AppVeyor](https://img.shields.io/appveyor/ci/charris/numpy/master.svg?label=AppVeyor)](
    https://ci.appveyor.com/project/charris/numpy)
[![Azure](https://dev.azure.com/numpy/numpy/_apis/build/status/azure-pipeline%20numpy.numpy)](
    https://dev.azure.com/numpy/numpy/_build/latest?definitionId=5)
[![codecov](https://codecov.io/gh/numpy/numpy/branch/master/graph/badge.svg)](
    https://codecov.io/gh/numpy/numpy)

NumPy 是使用 Python 做科学计算时所需的基础包。

- **官方网站 (包括文档):** https://www.numpy.org
- **邮件列表:** https://mail.python.org/mailman/listinfo/numpy-discussion
- **开源站点:** https://github.com/numpy/numpy
- **Bug 报告:** https://github.com/numpy/numpy/issues
- **贡献站点:** https://www.numpy.org/devdocs/dev/index.html

NumPy 提供了:

- 一种强力的多空间阵列对象
- 许多娴熟的 (广泛使用的) 函数
- 许多工具都集成了 C/C++ 和 Fortran 代码
- 许多有用的线性代数、傅立叶变换和随机数能力

测试:

- NumPy 版本大于等于 1.15 需要使用 `pytest` 进行测试
- NumPy 版本小于 1.15 需要使用 `nose` 进行测试

许多测试可以安装后通过运行如下命令来进行测试：

    python -c 'import numpy; numpy.test()'

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)
