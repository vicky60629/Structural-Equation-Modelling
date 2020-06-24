# Structured-Equation-Modelling

## Table of Content
  * [Overview](#overview)
  * [Directory Tree](#directory-tree)
  * [License](#license)

### Overview

Structural equation modelling (SEM) is a multivariate statistical technique for estimating complex relationships between observed and latent variables. Although numerous SEM packages exist, each of them has limitations. Some packages are not free or open-source; the most popular package not having this disadvantage is lavaan, but it is written in R language, which is behind current mainstream tendencies that make it harder to be incorporated into developmental pipelines (i.e. bioinformatical ones). Thus we developed the Python package semopy to satisfy those criteria. The paper provides detailed examples of package usage and explains it's inner clockworks. Moreover, we developed the unique generator of SEM models to extensively test SEM packages and demonstrated that semopy significantly outperforms lavaan in execution time and accuracy.

### Directory Tree

```
├── Structural Equation Modelling.ipynb
├── file.csv
LICENSE
├── README.md
```

### License

[MIT License](https://github.com/vicky60629/Structural-Equation-Modelling/blob/master/LICENSE)

Copyright (c) 2020 Vicky Gupta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
