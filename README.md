# qmlspectrum

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python3](https://img.shields.io/badge/Language-Python3-red.svg)](https://www.python.org/download/releases/3.0/)
![Domain: Chemistry](https://img.shields.io/badge/Domain-Chemistry-green.svg)

`qmlspectrum` is a small test-suite that uses [qml](https://www.qmlcode.org/) package for modeling spectra as continuous functions. In this repository, we also distribute suitable datasets suitable for spectral modeling. Example input scripts collected in `example_scripts` show how to use the `qmlspectrum` test-suite.

## Status

We are developing new content through collaborative efforts which will soon be collected here. 

## Installation

`qmlspectrum` can be installed using the Python package manager `pip3`

```
pip3 install qmlspectrum --user
```

## Dependencies

* `matplitlib`, `pandas`, `scipy`, `numpy`, `os`, `qml` all of which can be installed using the Python package manager `pip3`

## Contributors 

* Prakriti Kayastha    
* Arpan Chaudury     
* Sabysachi Chakraborty     
* Debashree Ghosh   
* Raghunathan Ramakrishnan    

## Development

This test-suite is developed by Raghunathan Ramakrishnan and maintained at [https://github.com/raghurama123/qmlspectrum/](https://github.com/raghurama123/qmlspectrum/) and [https://pypi.org/project/qmlspectrum/](https://pypi.org/project/qmlspectrum/)   

## Citation

If you are using the program and the bigQM7ω dataset distributed here, please consider citing the following article and the QML code.        

#### bigQM7ω dataset and full-spectrum modeling
[_Quantum Machine Learning Transition Probabilities in Electronic Excitation Spectra across Chemical Space: The Resolution-vs.-Accuracy Dilemma_](https://arxiv.org/abs/2110.11798)                
Prakriti Kayastha, Sabyasachi Chakraborty, Raghunathan Ramakrishnan (2022)     
```
@article{kayastha2022quantum,
  title={Quantum Machine Learning Transition Probabilities in Electronic Excitation 
  Spectra across Chemical Space: The Resolution-vs.-Accuracy Dilemma},
  author={Kayastha, Prakriti and Chakraborty, Sabyasachi and Ramakrishnan, Raghunathan},
  journal={arXiv preprint arXiv:2110.11798},
  url={https://doi.org/10.48550/arXiv.2110.11798},
  year={2022}
}
```

#### QML, A Python Toolkit for Quantum Machine Learning
[_AS Christensen, FA Faber, B Huang, LA Bratholm, A Tkatchenko, KR Muller, OA von Lilienfeld (2017) "QML: A Python Toolkit for Quantum Machine Learning, https://github.com/qmlcode/qml"_](https://github.com/qmlcode/qml)  
```
@misc{christensenqml,
  title={QML: A Python Toolkit for Quantum Machine Learning, 2019},
  author={Christensen, Anders S and Bratholm, Lars A and Amabilino, Silvia and Kromann, Jimmy C 
  and Faber, Felix A and Huang, Bing and Tkatchenko, A and von Lilienfeld, OA}
  url={https://www.qmlcode.org/}
}
```
