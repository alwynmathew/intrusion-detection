# Intrusion Detection at ATMs

Its crucial for financial systems to have sound security measures in place. For security reasons customers are not
allowed to wear a helmet while using ATM(Automated Teller Machine). An automated helmet detection using
ATM surveillance camera feed can help improve security significantly. Recently deep convolutional neural network
(DCNN) have shown state of the art accuracy in object detection and localization. In this work, a pretrained
Google’s inception v3 model have been used and have achieved an accuracy of 95.3% by training the model on a
proprietary ATM surveillance dataset. Transferred information from inception model has been feed to multiple fully
connected layers with drop outs to achieve better accuracy.

https://doi.org/10.1016/j.procs.2017.09.132

# Files

* Intrusion+detection.ipynb - main file
* download.py - Load dataset
* inception.py - Functions and classes for loading and using the Inception model

# Citation

If you find this useful for your research, please use the following.

```
@article{mathew2017improved,
  title={An Improved Transfer learning Approach for Intrusion Detection},
  author={Mathew, Alwyn and Mathew, Jimson and Govind, Mahesh and Mooppan, Asif},
  journal={Procedia Computer Science},
  volume={115},
  pages={251--257},
  year={2017},
  publisher={Elsevier}
}
```
