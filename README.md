# ICLR Reproducibility Challenge: Generative Adversarial Models For Learning Private And Fair Representations

We present code reproducing some of the results for a paper submitted to ICLR'19 entitled [Generative Adversarial Models for Learning Private and Fair Representations](https://openreview.net/forum?id=H1xAH2RqK7&fbclid=IwAR14io5Srnvw7SyErKCL52Bi7ONr6FtOqVSuJqTIQxZ2rb36nE7Ki8tjzBI). This paper explores using a generative adversarial model as a decorrelation mechanism that hides a sensitive variable while still preserving the utility of the original data. In our work, we replicated the architecture described in the paper using PyTorch and show a successful use case for the Human Activity Recognition (HAR) dataset.

## Repository Structure

The primary experiments and code are presented in an Jupyter Notebook, [iclr_har_reproduced.ipynb](iclr_har_reproduced.ipynb). The notebook requires `PyTorch`, `Pandas`, `numpy`, and `matplotlib` to run.

This project was completed in part as a final project for the Georgia Tech class [CS7643 Deep Learning](https://www.cc.gatech.edu/classes/AY2019/cs7643_fall/). As part of our submission, we [created a website](project_webpage/index.html) explaining our process and results.

We also attempted to apply the model to a novel dataset, the UCI Adult dataset, with limited results in [iclr_har_reproduced.ipynb](iclr_har_reproduced.ipynb).

## Researchers

|  Name                 | Affiliation                     |
|-----------------------|---------------------------------|
| [Angel Alexander Cabrera](http://cabreraalex.com)           | Georgia Tech |
| [Varun Gupta](https://www.linkedin.com/in/varun-gupta-80a18b106/)   | Georgia Tech |
| [Will Epperson](http://willepperson.com)        | Georgia Tech |

## Links

* [Original Paper Submission](https://openreview.net/forum?id=H1xAH2RqK7&fbclid=IwAR14io5Srnvw7SyErKCL52Bi7ONr6FtOqVSuJqTIQxZ2rb36nE7Ki8tjzBI)
* [CS7643 Deep Learning](https://www.cc.gatech.edu/classes/AY2019/cs7643_fall/)
* [Reproducibility Challenge](https://reproducibility-challenge.github.io/iclr_2019/)
* [GitHub Tracker](https://github.com/reproducibility-challenge/iclr_2019/issues/72)
