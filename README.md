# ACCORD_KFRE

This repository contains code to reproduce the results presented in the paper 

> **Charu V, Liang JW, Chertow GM, Li J, Montez-Rath ME, Geldsetzer, P, de Boer I, Tian Lu, Kurella Tamura M. Heterogeneous treatment effects of intensive glycemic control on kidney microvascular outcomes in ACCORD. 2023.**
  
## R package dependencies
- Data wrangling and visualization: [`tidyverse`](https://cran.r-project.org/web/packages/tidyverse/index.html) and [`survminer`](https://cran.r-project.org/web/packages/survminer/index.html)
- Model fitting and evaluation: [`survival`](https://cran.r-project.org/web/packages/survival/index.html) and [`survRM2`](https://cran.r-project.org/web/packages/survRM2/index.html)
- Parellelization: [`foreach`](https://cran.r-project.org/web/packages/foreach/index.html) and [`doParallel`](https://cran.r-project.org/web/packages/doParallel/index.html)

## Data
- Action to Control Cardiovascular Risk in Diabetes (ACCORD) study data<sup>[1](#myfootnote1), [2](#myfootnote2)</sup>

---

<a name="myfootnote1">1</a>. Action to Control Cardiovascular Risk in Diabetes Study Group, Gerstein HC, Miller ME, et al. Effects of intensive glucose lowering in type 2 diabetes. *N Engl J Med*. 2008;358(24):2545-2559. doi:10.1056/NEJMoa0802743

<a name="myfootnote2">2</a>. Ismail-Beigi F, Craven T, Banerji MA, et al. Effect of intensive treatment of hyperglycaemia on microvascular outcomes in type 2 diabetes: an analysis of the ACCORD randomised trial. *Lancet*. 2010;376(9739):419-430. doi:10.1016/S0140-6736(10)60576-4
